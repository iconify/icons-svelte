<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdkjc0b1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="bdkjc0b1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:throw" {...props}></Icon>
