<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc-w-0b1k.css';
import '../../css/r/rihw2qt5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mc-w-0b1k"/><path class="rihw2qt5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:traffic-lights-line" {...props}></Icon>
