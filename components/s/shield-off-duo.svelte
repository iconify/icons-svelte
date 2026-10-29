<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/whz-6eqqw.css';
import '../../css/q/qr4ochb5c.css';
import '../../css/r/ri2e-qbwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="whz-6eqqw"/><path class="qr4ochb5c wm-s"/><path class="ri2e-qbwa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shield-off-duo" {...props}></Icon>
