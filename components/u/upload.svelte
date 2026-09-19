<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yeb0kmifh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":666};
const content = `<path class="yeb0kmifh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:upload" {...props}></Icon>
