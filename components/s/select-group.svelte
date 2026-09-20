<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfro8_bsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfro8_bsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:select-group" {...props}></Icon>
