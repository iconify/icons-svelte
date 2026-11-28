<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1w119vdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1w119vdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:trophy-star-solid" {...props}></Icon>
