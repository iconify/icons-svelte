<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haxv7wbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="haxv7wbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-lock-line" {...props}></Icon>
