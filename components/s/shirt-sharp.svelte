<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6-v5-b8g.css';
import '../../css/s/spmrb2bwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e6-v5-b8g"/><path class="spmrb2bwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:shirt-sharp" {...props}></Icon>
