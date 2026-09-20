<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4ou9x3zt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4ou9x3zt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:slider" {...props}></Icon>
