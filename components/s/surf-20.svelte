<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t62z6ibns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t62z6ibns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:surf-20" {...props}></Icon>
