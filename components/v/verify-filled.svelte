<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk5d2mhzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qk5d2mhzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:verify-filled" {...props}></Icon>
