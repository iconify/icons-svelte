<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zva9y3b3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zva9y3b3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:text-tracking" {...props}></Icon>
