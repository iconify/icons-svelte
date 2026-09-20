<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_3ltgb8o.css';
import '../../css/d/dk4tjtb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s_3ltgb8o"/><path class="dk4tjtb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:vending-cold-drink2" {...props}></Icon>
