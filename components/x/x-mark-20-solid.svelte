<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-lno9bif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f-lno9bif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:x-mark-20-solid" {...props}></Icon>
