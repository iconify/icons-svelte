<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp44fybpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="lp44fybpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:window-20-solid" {...props}></Icon>
