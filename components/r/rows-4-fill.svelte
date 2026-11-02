<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijb73rbzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijb73rbzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rows-4-fill" {...props}></Icon>
