<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1mpicbvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="y1mpicbvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:user-circle" {...props}></Icon>
