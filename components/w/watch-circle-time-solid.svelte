<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vot7kibza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vot7kibza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:watch-circle-time-solid" {...props}></Icon>
