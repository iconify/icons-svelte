<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5nnmsbvd.css';
import '../../css/f/f3hc-8p1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m5nnmsbvd"/><path class="f3hc-8p1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:stamp-stroke-20" {...props}></Icon>
