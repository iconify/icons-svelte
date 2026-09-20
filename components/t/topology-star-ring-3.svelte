<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzvxr8jxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jzvxr8jxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:topology-star-ring-3" {...props}></Icon>
