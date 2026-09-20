<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktdhq7xuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktdhq7xuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:settings-play-outline" {...props}></Icon>
