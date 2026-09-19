<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz8difb4r.css';
import '../../css/q/qne2hd_ir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fz8difb4r"/><path class="qne2hd_ir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:unite" {...props}></Icon>
