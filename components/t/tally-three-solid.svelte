<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgt-5pbmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qgt-5pbmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:tally-three-solid" {...props}></Icon>
