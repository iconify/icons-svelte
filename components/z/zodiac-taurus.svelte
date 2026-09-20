<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e67a4j29f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e67a4j29f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:zodiac-taurus" {...props}></Icon>
