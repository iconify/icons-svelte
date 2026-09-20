<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhln61bon.css';
import '../../css/m/mvx_vib_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhln61bon"/><path clip-rule="evenodd" class="mvx_vib_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-pin-fill" {...props}></Icon>
