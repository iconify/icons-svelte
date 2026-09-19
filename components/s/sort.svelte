<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2i_l0snn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="x2i_l0snn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:sort" {...props}></Icon>
