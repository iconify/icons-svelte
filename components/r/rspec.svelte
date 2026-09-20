<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzghodlei.css';
import '../../css/f/f9yyg-b3m.css';
import '../../css/u/uys2z4s7k.css';
import '../../css/r/r1tlpd6cz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="dzghodlei"/><path class="f9yyg-b3m"/><path class="uys2z4s7k"/><path class="r1tlpd6cz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rspec" {...props}></Icon>
