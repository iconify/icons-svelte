<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_3ltgb8o.css';
import '../../css/o/o9p1ubbpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s_3ltgb8o"/><path class="o9p1ubbpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:vending-hot-drink2" {...props}></Icon>
