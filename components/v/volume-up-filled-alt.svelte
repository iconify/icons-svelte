<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnj4z1-0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nnj4z1-0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:volume-up-filled-alt" {...props}></Icon>
