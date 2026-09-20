<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7hbd3-ms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="o7hbd3-ms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:ruble" {...props}></Icon>
