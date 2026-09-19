<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/os8x0cc1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="os8x0cc1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:tower-broadcast" {...props}></Icon>
