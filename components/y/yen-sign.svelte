<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk-9l5boc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="kk-9l5boc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:yen-sign" {...props}></Icon>
