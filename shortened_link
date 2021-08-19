$a = 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Aperiam nulla, quo tenetur cumque eius minus autem aspernatur possimus ipsa recusandae laudantium. Numquam commodi corporis molestias excepturi modi eligendi provident dolorum.Lorem ipsum dolor sit amet consectetur adipisicing elit. Aperiam nulla, quo tenetur cumque eius minus autem aspernatur possimus ipsa recusandae laudantium. Numquam commodi corporis molestias excepturi modi eligendi provident dolorum.Lorem ipsum dolor sit amet consectetur adipisicing elit. Aperiam nulla, quo tenetur cumque eius minus autem aspernatur possimus ipsa recusandae laudantium. Numquam commodi corporis molestias excepturi modi eligendi provident dolorum.Lorem ipsum dolor sit amet consectetur adipisicing elit. Aperiam nulla, quo tenetur cumque eius minus autem aspernatur possimus ipsa recusandae laudantium. Numquam commodi corporis molestias excepturi modi eligendi provident dolorum.Lorem ipsum dolor sit amet consectetur adipisicing elit. Aperiam nulla, quo tenetur cumque eius minus autem aspernatur possimus ipsa recusandae laudantium. Numquam commodi corporis molestias excepturi modi eligendi provident dolorum.';
$link = 'link.php';
function shortened_link($fullText, $link)
{
    $shortening = substr($fullText, 0, 180) . '...';
    $splitting = explode(' ', $fullText);
    $replace = $splitting[str_word_count($shortening) - 2] . ' ' . $splitting[str_word_count($shortening) - 1];
    return str_replace($replace, "<a href = '$link'>" . $replace . "</a>", $shortening);
}
echo shortened_link($a, $link);
