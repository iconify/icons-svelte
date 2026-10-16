<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9f_3wnku.css';
import '../../css/n/n-pf8dtms.css';
import '../../css/t/tn_egrb9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e9f_3wnku"/><path class="n-pf8dtms"/><path class="tn_egrb9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:text-size-20" {...props}></Icon>
