<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vovp7w37k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="vovp7w37k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:stackblitz" {...props}></Icon>
