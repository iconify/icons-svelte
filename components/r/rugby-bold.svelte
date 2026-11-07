<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-mei2b6d.css';
import '../../css/n/nudj6ubep.css';
import '../../css/g/gl_0n93vk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-mei2b6d"/><path class="nudj6ubep"/><path clip-rule="evenodd" class="gl_0n93vk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rugby-bold" {...props}></Icon>
