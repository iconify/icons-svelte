<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/paev8qj-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="paev8qj-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:signal-high-20" {...props}></Icon>
