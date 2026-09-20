<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1us_l5nc.css';
import '../../css/f/fd1zf2m-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="g1us_l5nc"/><path class="fd1zf2m-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:shadcn-ui-dark" {...props}></Icon>
