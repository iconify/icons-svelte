<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyvso6b0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qyvso6b0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:triangle-20" {...props}></Icon>
