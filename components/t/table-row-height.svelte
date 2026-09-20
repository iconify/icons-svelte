<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3is5gdlo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3is5gdlo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:table-row-height" {...props}></Icon>
