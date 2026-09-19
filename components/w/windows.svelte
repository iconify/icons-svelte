<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/secm1-tlc.css';
import '../../css/o/ozzrz2p5p.css';
import '../../css/v/v_3i9wmxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secm1-tlc"/><path class="ozzrz2p5p"/><path class="v_3i9wmxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:windows" {...props}></Icon>
