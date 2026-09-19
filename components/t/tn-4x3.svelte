<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-p6sxs_x.css';
import '../../css/i/ibd8u0c8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="m-p6sxs_x"/><path class="ibd8u0c8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:tn-4x3" {...props}></Icon>
