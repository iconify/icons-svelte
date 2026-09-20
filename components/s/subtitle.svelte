<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlazx1s9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="nlazx1s9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:subtitle" {...props}></Icon>
