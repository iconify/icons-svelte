<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvj7x-bex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="uvj7x-bex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:square-pinterest" {...props}></Icon>
