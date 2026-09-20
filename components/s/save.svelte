<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vponrbbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vponrbbbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:save" {...props}></Icon>
