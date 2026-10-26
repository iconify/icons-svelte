<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_b5g604s.css';
import '../../css/c/c3p99coiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":263.33,"height":173.53};
const content = `<path class="y_b5g604s"/><ellipse class="c3p99coiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rybbit-light" {...props}></Icon>
