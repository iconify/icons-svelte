<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o60kez9_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o60kez9_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:warning-filled" {...props}></Icon>
