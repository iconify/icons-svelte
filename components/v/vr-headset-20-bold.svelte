<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9wztb3tr.css';
import '../../css/d/d3xoy3b4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v9wztb3tr"/><path class="d3xoy3b4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:vr-headset-20-bold" {...props}></Icon>
