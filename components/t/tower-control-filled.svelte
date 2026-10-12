<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjr_e6btm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjr_e6btm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:tower-control-filled" {...props}></Icon>
