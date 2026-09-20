<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p305i0r_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p305i0r_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:wax" {...props}></Icon>
