<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5zp9z6sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="i5zp9z6sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:wrench" {...props}></Icon>
