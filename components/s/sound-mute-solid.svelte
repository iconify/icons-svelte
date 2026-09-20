<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo-hi3hch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uo-hi3hch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:sound-mute-solid" {...props}></Icon>
