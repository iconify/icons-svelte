<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktb81tbfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ktb81tbfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:warning-filled" {...props}></Icon>
