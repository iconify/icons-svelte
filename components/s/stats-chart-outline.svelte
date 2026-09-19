<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wry-w1bxn.css';
import '../../css/n/nyurgsbqe.css';
import '../../css/d/djgk4x_3w.css';
import '../../css/z/z16su76ar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="wry-w1bxn"/><rect class="nyurgsbqe"/><rect class="djgk4x_3w"/><rect class="z16su76ar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:stats-chart-outline" {...props}></Icon>
