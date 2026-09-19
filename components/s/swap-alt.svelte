<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk7i8db5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="hk7i8db5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:swap-alt" {...props}></Icon>
