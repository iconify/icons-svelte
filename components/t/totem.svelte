<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uujz0sipy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="uujz0sipy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:totem" {...props}></Icon>
