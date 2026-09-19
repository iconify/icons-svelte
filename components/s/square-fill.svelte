<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cldxv2gkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cldxv2gkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:square-fill" {...props}></Icon>
