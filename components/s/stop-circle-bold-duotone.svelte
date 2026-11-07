<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpv5vhdla.css';
import '../../css/c/c36_0z9jv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpv5vhdla"/><path class="c36_0z9jv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:stop-circle-bold-duotone" {...props}></Icon>
