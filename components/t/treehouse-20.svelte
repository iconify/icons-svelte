<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyb_tsrjh.css';
import '../../css/k/k8mwnmlmr.css';
import '../../css/b/bxpdewbnx.css';
import '../../css/x/x2g6pju7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cyb_tsrjh"/><path class="k8mwnmlmr"/><path class="bxpdewbnx"/><path class="x2g6pju7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:treehouse-20" {...props}></Icon>
