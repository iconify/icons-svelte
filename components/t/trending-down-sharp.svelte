<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4a-oac3f.css';
import '../../css/k/klwyf98zv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q4a-oac3f"/><path class="klwyf98zv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:trending-down-sharp" {...props}></Icon>
