<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oonyl_b5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":897};
const content = `<path class="oonyl_b5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:tshirt" {...props}></Icon>
