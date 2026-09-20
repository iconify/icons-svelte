<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7skdvj0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="c7skdvj0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:subscript" {...props}></Icon>
