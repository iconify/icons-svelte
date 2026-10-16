<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajach0a3z.css';
import '../../css/f/fyvg948cl.css';
import '../../css/x/xpigs6blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ajach0a3z"/><path class="fyvg948cl"/><path class="xpigs6blj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sluice-gate-20" {...props}></Icon>
