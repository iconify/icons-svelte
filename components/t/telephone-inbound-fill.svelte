<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uiok6x51q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uiok6x51q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:telephone-inbound-fill" {...props}></Icon>
