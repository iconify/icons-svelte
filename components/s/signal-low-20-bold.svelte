<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsw7geboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bsw7geboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:signal-low-20-bold" {...props}></Icon>
