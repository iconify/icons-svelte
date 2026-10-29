<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu-umyrwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cu-umyrwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:sigma-solid" {...props}></Icon>
