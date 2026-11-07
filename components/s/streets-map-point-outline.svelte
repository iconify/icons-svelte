<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-ejzngjy.css';
import '../../css/r/rc0x7kb9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q-ejzngjy"/><path class="rc0x7kb9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:streets-map-point-outline" {...props}></Icon>
