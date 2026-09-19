<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy_qmbbxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="gy_qmbbxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:turkish-lira-sign" {...props}></Icon>
