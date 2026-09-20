<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so4zo0bpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="so4zo0bpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:tally-two-solid" {...props}></Icon>
