<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcu23r-dh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcu23r-dh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sim-card-2-line" {...props}></Icon>
