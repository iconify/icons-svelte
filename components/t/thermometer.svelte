<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn5ch7ksf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yn5ch7ksf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:thermometer" {...props}></Icon>
