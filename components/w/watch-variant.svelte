<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d91y7tbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d91y7tbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:watch-variant" {...props}></Icon>
