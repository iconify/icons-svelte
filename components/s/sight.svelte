<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx_1zebpd.css';
import '../../css/i/i2ck-cb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qx_1zebpd"/><path class="i2ck-cb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:sight" {...props}></Icon>
