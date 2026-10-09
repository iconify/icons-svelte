<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzx5mchnl.css';
import '../../css/w/w2wr_lj5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xzx5mchnl"/><path class="w2wr_lj5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:saw-48-bold" {...props}></Icon>
