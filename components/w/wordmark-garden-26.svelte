<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktrn7m7cc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":73,"height":26};
const content = `<path class="ktrn7m7cc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:wordmark-garden-26" {...props}></Icon>
