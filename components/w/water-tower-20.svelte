<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i16ny7bvz.css';
import '../../css/e/e3jspeiln.css';
import '../../css/d/duvqrbc-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i16ny7bvz"/><path class="e3jspeiln"/><path class="duvqrbc-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:water-tower-20" {...props}></Icon>
