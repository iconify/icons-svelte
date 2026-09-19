<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tos7grkdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tos7grkdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:skip-back-filled" {...props}></Icon>
