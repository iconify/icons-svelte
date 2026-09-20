<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/em2nqve8q.css';
import '../../css/n/n5k9wlmuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="em2nqve8q"/><path class="n5k9wlmuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:weight" {...props}></Icon>
