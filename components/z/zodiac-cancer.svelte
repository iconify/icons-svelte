<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxsnx8oha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxsnx8oha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:zodiac-cancer" {...props}></Icon>
