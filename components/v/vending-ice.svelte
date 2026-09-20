<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_3ltgb8o.css';
import '../../css/o/ojl0pt7uj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s_3ltgb8o"/><path class="ojl0pt7uj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:vending-ice" {...props}></Icon>
