<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoui6huvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xoui6huvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:thealgorithms" {...props}></Icon>
