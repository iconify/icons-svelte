<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvezj4bst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvezj4bst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:text-centerline-center-top" {...props}></Icon>
