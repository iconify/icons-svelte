<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu5gjko1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":448};
const content = `<path class="lu5gjko1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:tacos" {...props}></Icon>
