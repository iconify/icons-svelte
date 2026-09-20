<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmasnh69x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="tmasnh69x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:skipping-rope" {...props}></Icon>
