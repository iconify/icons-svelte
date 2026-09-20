<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-tu_s2fd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-tu_s2fd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:spam-fill" {...props}></Icon>
