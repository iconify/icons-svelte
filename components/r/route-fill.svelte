<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5sa_0a6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5sa_0a6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:route-fill" {...props}></Icon>
