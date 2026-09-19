<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rldz3bb1z.css';
import '../../css/w/wdrk3cy4t.css';
import '../../css/p/p8wh8o_bf.css';
import '../../css/s/s0qlh1b2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="rldz3bb1z"/><path class="wdrk3cy4t"/><path class="p8wh8o_bf"/><path class="s0qlh1b2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:sfml" {...props}></Icon>
