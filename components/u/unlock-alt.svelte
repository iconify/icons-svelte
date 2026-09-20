<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh4a7_p0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yh4a7_p0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:unlock-alt" {...props}></Icon>
