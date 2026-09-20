<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omq1hqcfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="omq1hqcfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:white-balance-incandescent" {...props}></Icon>
