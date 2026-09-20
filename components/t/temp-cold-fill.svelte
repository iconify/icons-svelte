<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ueuic50-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ueuic50-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:temp-cold-fill" {...props}></Icon>
