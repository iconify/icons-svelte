<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbifotbyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="nbifotbyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:sidebar-simple-bottom" {...props}></Icon>
