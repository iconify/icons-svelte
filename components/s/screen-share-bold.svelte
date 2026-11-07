<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxpbg7b-b.css';
import '../../css/k/k4l1xjb4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kxpbg7b-b"/><path class="k4l1xjb4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:screen-share-bold" {...props}></Icon>
