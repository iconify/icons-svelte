<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvomfubey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="pvomfubey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:zodiac-8" {...props}></Icon>
