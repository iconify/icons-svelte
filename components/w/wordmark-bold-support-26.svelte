<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce1150bat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":78,"height":26};
const content = `<path class="ce1150bat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:wordmark-bold-support-26" {...props}></Icon>
