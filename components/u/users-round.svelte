<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suw5ydbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="suw5ydbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:users-round" {...props}></Icon>
