<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od_h8eb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="od_h8eb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:yen-circle" {...props}></Icon>
