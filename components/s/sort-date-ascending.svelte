<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo9gcnbpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zo9gcnbpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sort-date-ascending" {...props}></Icon>
