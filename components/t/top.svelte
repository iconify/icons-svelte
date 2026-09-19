<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1xy3gbno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="y1xy3gbno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:top" {...props}></Icon>
