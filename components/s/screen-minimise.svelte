<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evkjnzbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="evkjnzbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:screen-minimise" {...props}></Icon>
