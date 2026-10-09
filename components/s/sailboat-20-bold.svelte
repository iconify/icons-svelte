<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxh9rydyd.css';
import '../../css/a/aexs-bb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kxh9rydyd"/><path class="aexs-bb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sailboat-20-bold" {...props}></Icon>
