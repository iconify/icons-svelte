<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu19h5b1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="hu19h5b1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:star" {...props}></Icon>
