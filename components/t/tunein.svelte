<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1jqi3bfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="k1jqi3bfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:tunein" {...props}></Icon>
