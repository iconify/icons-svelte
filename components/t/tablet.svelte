<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofi5qkbay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ofi5qkbay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:tablet" {...props}></Icon>
