<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8j5tt9nv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s8j5tt9nv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shield-check-solid" {...props}></Icon>
