<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1rnrcbzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a1rnrcbzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:tree" {...props}></Icon>
