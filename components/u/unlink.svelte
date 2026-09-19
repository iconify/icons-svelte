<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3awiw91z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v3awiw91z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:unlink" {...props}></Icon>
