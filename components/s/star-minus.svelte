<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us2ogcqly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="us2ogcqly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:star-minus" {...props}></Icon>
