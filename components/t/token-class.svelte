<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qapc79bwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qapc79bwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-class" {...props}></Icon>
