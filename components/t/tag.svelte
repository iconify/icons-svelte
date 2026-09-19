<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgmga3btl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":666,"height":668};
const content = `<path class="lgmga3btl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:tag" {...props}></Icon>
