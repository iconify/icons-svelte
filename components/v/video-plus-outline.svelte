<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0pn1_bxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0pn1_bxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:video-plus-outline" {...props}></Icon>
