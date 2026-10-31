<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r986gcbmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r986gcbmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:user-check-corner-round" {...props}></Icon>
