<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f86a2l21j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f86a2l21j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:video-standard-definition" {...props}></Icon>
