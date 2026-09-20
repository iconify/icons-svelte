<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re_gkwr9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="re_gkwr9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:swap-box-line" {...props}></Icon>
