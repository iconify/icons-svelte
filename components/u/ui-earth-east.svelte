<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9sb1r7in.css';
import '../../css/z/zmirjg79h.css';
import '../../css/b/b6spzmbdx.css';
import '../../css/m/mai5xwbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="f9sb1r7in"/><path class="zmirjg79h"/><path class="b6spzmbdx"/><path class="mai5xwbnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="geo:ui-earth-east" {...props}></Icon>
