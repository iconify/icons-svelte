<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj8l9tbqx.css';
import '../../css/v/vqd8c7baf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":16};
const content = `<path class="nj8l9tbqx"/><path class="vqd8c7baf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:upload" {...props}></Icon>
