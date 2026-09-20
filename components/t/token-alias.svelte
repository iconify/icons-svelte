<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujkfyy2pr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ujkfyy2pr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-alias" {...props}></Icon>
