<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz542cbqq.css';
import '../../css/r/rv4rin_vb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vz542cbqq"/><path class="rv4rin_vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:save" {...props}></Icon>
