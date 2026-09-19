<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk6666kbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rk6666kbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:sold-out" {...props}></Icon>
