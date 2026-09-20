<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1i9edblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="k1i9edblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:upward" {...props}></Icon>
