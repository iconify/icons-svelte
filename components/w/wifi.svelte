<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft81j6ddr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="ft81j6ddr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:wifi" {...props}></Icon>
