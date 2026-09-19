<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo11wvb4j.css';
import '../../css/h/htivmtpeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mo11wvb4j"/><path class="htivmtpeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shape-trim-alt-filled" {...props}></Icon>
