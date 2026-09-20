<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo7_cnbhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bo7_cnbhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:theplanetarysociety" {...props}></Icon>
