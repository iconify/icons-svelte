<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n86bdsxzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n86bdsxzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:traffic-cone" {...props}></Icon>
