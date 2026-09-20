<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smnye9b4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smnye9b4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:terminal-asterisk-sharp-fill" {...props}></Icon>
