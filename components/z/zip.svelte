<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak2v05c1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ak2v05c1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:zip" {...props}></Icon>
