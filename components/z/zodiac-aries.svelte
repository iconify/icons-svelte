<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-_oh8f1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-_oh8f1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:zodiac-aries" {...props}></Icon>
