<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck9wswbnb.css';
import '../../css/a/aifu62-rj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ck9wswbnb"/><path class="aifu62-rj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smartphone-20" {...props}></Icon>
