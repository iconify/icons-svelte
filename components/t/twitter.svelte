<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ize7-b.css';
import '../../css/s/so-from-62.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ize7-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:twitter" {...props}></Icon>
