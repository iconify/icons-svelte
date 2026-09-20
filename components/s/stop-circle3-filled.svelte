<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb8r_pb9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kb8r_pb9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:stop-circle3-filled" {...props}></Icon>
