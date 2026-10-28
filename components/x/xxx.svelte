<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/why_b6bde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="why_b6bde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:xxx" {...props}></Icon>
