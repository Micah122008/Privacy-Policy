# Privacy-Policy
import React from "react";
// import { Link } from "react-router-dom";
import NavbarDefault from "layouts/marketing/navbars/NavbarDefault";
import FooterWithLinks from "layouts/marketing/footers/FooterWithLinks";
import "./whitebackground.css";
import {
  Col,
  Row,
  Card,
  //  Form, Button
} from "react-bootstrap";

// import media files

const PrivacyPolicy = () => {
  return (
    <React.Fragment>
      <NavbarDefault login />

      <Row className="align-items-center justify-content-center g-0 min-vh-100">
        <Col lg={5} md={5} className="py-8 py-xl-0">
          <Card className="white-background-privacy-policy">
            <Card.Body className="p-6">
              <div>
                <p>
                  <h3>
                    Privacy Statement: This Privacy Statement explains how we
                    collect, use, and disclose your personal information when
                    you use the Ojalá service to access “Ojalá content” as those
                    terms are defined in the Ojalá Terms of Use
                    (ojalá.com/terms). It also explains what privacy rights you
                    have and how to exercise them. Certain functionalities or
                    apps that are part of the Ojalá service may also provide you
                    with contextual privacy information or choices, in addition
                    to the information and choices described in this Privacy
                    Statement. Please note that this Privacy Statement may be
                    easier to navigate when viewed on your web browser. To see
                    our California Consumer Privacy Act (CCPA) Privacy Notice,
                    including “Notice at Collection” details, please click on
                    the link, go to ojalá.com/privacy#ccpa, or scroll down to
                    the “Supplemental Privacy Disclosures for US Residents”
                    section. Contacting Us For questions about this Privacy
                    Statement, our use of your personal information, or how to
                    exercise your privacy rights, please contact our Data
                    Protection Officer/Privacy Office at privacy@ojalá.com. For
                    general questions about the Ojalá service, your account, or
                    how to contact customer service, please visit
                    help.ojalá.com. Information about the specific Ojalá entity
                    (or entities) that are responsible for your personal
                    information (known as the “data controller” in certain
                    countries) is available at ojalá.com/legal/corpinfo.
                  </h3>
                </p>
              </div>
            </Card.Body>
          </Card>
        </Col>
      </Row>
      <FooterWithLinks />
    </React.Fragment>
  );
};

export default PrivacyPolicy;
