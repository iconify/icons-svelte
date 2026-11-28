<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqw14dbpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zqw14dbpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:user-circle" {...props}></Icon>
