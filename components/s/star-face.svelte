<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugeu1-b-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugeu1-b-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:star-face" {...props}></Icon>
