<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqsb49kgr.css';
import '../../css/a/ahzc34b2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lqsb49kgr"/><path class="ahzc34b2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:signature-20-bold" {...props}></Icon>
