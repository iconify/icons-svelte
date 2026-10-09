<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9zz2bdnl.css';
import '../../css/g/gx1h2ob_o.css';
import '../../css/b/bof50_b9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f9zz2bdnl"/><path class="gx1h2ob_o"/><path class="bof50_b9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:villa-20-bold" {...props}></Icon>
