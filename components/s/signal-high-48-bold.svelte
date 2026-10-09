<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-zi6-bjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i-zi6-bjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:signal-high-48-bold" {...props}></Icon>
