<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdag2ccwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-1,"top":-1};
const content = `<path class="fdag2ccwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:screwdriver" {...props}></Icon>
