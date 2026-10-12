<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i79j4xzwx.css';
import '../../css/h/hc_zcwc_j.css';
import '../../css/e/edh-75b4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i79j4xzwx"/><path class="hc_zcwc_j"/><path class="edh-75b4r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:truck-duotone" {...props}></Icon>
