<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5o7o8bjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5o7o8bjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:shield-cog-solid" {...props}></Icon>
