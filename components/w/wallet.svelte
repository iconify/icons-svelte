<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umk1w0oyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="umk1w0oyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:wallet" {...props}></Icon>
