<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voc11hbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="voc11hbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:stable" {...props}></Icon>
