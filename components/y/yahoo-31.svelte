<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr8hnubib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="vr8hnubib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:yahoo-31" {...props}></Icon>
