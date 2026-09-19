<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku5kwhbis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":1024};
const content = `<path class="ku5kwhbis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:voltage" {...props}></Icon>
