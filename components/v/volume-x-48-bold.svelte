<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgv66ypwa.css';
import '../../css/t/tzy1k5bvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xgv66ypwa"/><path class="tzy1k5bvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:volume-x-48-bold" {...props}></Icon>
