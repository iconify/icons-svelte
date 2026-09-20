<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3oyjbb4p.css';
import '../../css/e/e56i_o0sr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="j3oyjbb4p"/><path class="e56i_o0sr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:usb-cable-solid" {...props}></Icon>
