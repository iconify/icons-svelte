<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4c0kcz5z.css';
import '../../css/g/gjwv7pfic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4c0kcz5z"/><path class="gjwv7pfic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:usb-cable-bold" {...props}></Icon>
