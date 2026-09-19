<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/houfp_bzv.css';
import '../../css/h/h8_ziyb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="houfp_bzv"/><path class="h8_ziyb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:select-none-filled" {...props}></Icon>
