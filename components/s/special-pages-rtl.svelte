<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdf97fb-v.css';
import '../../css/e/e9nqe7b2h.css';
import '../../css/k/k8ixw89dy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mdf97fb-v"/><path class="e9nqe7b2h"/><path class="k8ixw89dy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:special-pages-rtl" {...props}></Icon>
