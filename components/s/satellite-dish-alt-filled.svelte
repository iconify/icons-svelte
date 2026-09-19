<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt3_b7qwc.css';
import '../../css/v/v14jurb5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gt3_b7qwc"/><path class="v14jurb5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:satellite-dish-alt-filled" {...props}></Icon>
