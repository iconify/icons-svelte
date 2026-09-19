<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myz8l2ote.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="myz8l2ote"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:text-align-middle" {...props}></Icon>
