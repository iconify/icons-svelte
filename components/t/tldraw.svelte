<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3o88hbsh.css';
import '../../css/q/q5chu0b0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v3o88hbsh"/><path class="q5chu0b0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tldraw" {...props}></Icon>
