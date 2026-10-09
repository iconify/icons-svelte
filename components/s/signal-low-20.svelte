<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6edurbtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c6edurbtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:signal-low-20" {...props}></Icon>
