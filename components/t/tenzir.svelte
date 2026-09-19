<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssvyn6bgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ssvyn6bgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:tenzir" {...props}></Icon>
