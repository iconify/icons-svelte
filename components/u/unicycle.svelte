<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qylidlbpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qylidlbpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:unicycle" {...props}></Icon>
