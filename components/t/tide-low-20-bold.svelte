<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qghjcac2i.css';
import '../../css/s/smcke3big.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qghjcac2i"/><path class="smcke3big"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tide-low-20-bold" {...props}></Icon>
