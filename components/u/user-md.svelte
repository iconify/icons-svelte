<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xma9i4bfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xma9i4bfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:user-md" {...props}></Icon>
