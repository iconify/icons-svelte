<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/coqe7zz9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="coqe7zz9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:tablet" {...props}></Icon>
