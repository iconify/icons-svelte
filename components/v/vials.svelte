<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxn4-qbhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dxn4-qbhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:vials" {...props}></Icon>
