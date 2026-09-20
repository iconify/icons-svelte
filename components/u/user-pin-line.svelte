<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps1e0_brw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ps1e0_brw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-pin-line" {...props}></Icon>
