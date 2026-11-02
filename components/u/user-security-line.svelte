<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh87xdf0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mh87xdf0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-security-line" {...props}></Icon>
