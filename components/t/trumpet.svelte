<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgbhe6bsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mgbhe6bsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:trumpet" {...props}></Icon>
