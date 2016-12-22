<h1><%= @student.to_s %></h1>
<p><%= is_active(@student) %></p>


def is_active(student)
  if student.active
    "This student is active"
  else
    "This student is inactive"
  end
end

# if self.active
#   self.active = false
# else
#   self.active = true
# end
