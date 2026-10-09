<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xalnqm_-k.css';
import '../../css/p/pjtb2zjhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xalnqm_-k"/><path class="pjtb2zjhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:square-check-20-bold" {...props}></Icon>
