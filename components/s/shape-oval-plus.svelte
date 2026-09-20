<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etw_cjf_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="etw_cjf_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shape-oval-plus" {...props}></Icon>
