<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzo8qqbnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wzo8qqbnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:shopping-code" {...props}></Icon>
