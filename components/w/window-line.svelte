<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt8o2hn_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dt8o2hn_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:window-line" {...props}></Icon>
