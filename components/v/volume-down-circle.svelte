<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy3_51b9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="xy3_51b9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:volume-down-circle" {...props}></Icon>
