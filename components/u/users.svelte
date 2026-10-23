<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csp1i_y1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="csp1i_y1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:users" {...props}></Icon>
