<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir2g77-jy.css';
import '../../css/f/faoz8ravc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ir2g77-jy"/><path class="faoz8ravc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:webhook-20" {...props}></Icon>
