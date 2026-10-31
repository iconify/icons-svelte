<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ww36v96hh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ww36v96hh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:settings-sparkle-round" {...props}></Icon>
