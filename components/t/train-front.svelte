<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp5qxlz_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zp5qxlz_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:train-front" {...props}></Icon>
