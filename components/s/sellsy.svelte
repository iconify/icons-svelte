<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnmhnfnsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="rnmhnfnsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:sellsy" {...props}></Icon>
