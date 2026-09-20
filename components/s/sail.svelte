<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o12k-dbaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="o12k-dbaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sail" {...props}></Icon>
