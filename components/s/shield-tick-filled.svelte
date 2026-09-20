<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfo71rzom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfo71rzom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:shield-tick-filled" {...props}></Icon>
