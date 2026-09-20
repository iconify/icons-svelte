<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szw_e6b1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szw_e6b1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:store-3-line" {...props}></Icon>
