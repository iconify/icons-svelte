<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryaeftb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ryaeftb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-terminal-asterisk-sharp-fill" {...props}></Icon>
