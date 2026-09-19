<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3j3b2bnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3j3b2bnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:toy-car-filled" {...props}></Icon>
