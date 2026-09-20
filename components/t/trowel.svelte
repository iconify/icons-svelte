<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib8c9xnsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ib8c9xnsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:trowel" {...props}></Icon>
