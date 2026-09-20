<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vddcv373l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vddcv373l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tag-hidden" {...props}></Icon>
