<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el-65cbhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="el-65cbhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:traffic-cone" {...props}></Icon>
