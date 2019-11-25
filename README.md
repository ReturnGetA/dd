Static.setModel(new javax.swing.DefaultComboBoxModel<>(new String[] { "Mean", "Med", "Mode" }));
        Static.setFocusCycleRoot(true);
        Static.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                StaticActionPerformed(evt);
            }
        });
        getContentPane().add(Static);	
        Static.setBounds(100, 100, 270, 30);
