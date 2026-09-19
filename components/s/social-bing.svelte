<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8e3o6bwj.css';
import '../../css/r/r0h4debhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<ellipse class="q8e3o6bwj"/><path class="r0h4debhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-bing" {...props}></Icon>
