<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m437_pb4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m437_pb4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:volvo-alt" {...props}></Icon>
