<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx53cu8on.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kx53cu8on"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wave-fill" {...props}></Icon>
