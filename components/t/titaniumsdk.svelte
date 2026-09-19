<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_dd5e65m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="q_dd5e65m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:titaniumsdk" {...props}></Icon>
