<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl04sjitv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="fl04sjitv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:sterling-sign" {...props}></Icon>
