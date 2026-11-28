<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn5jb6bbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="nn5jb6bbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:shield-x-bold" {...props}></Icon>
