<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw0wqacwc.css';
import '../../css/x/x0b3z4bzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lw0wqacwc"/><path class="x0b3z4bzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wifi-medium-20" {...props}></Icon>
