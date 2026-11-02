<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qoh6psbwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qoh6psbwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:stair-stepper-line" {...props}></Icon>
