<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrl4macvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hrl4macvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:stamp" {...props}></Icon>
