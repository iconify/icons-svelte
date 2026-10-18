<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwvmqj5ia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwvmqj5ia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:triangle-alert" {...props}></Icon>
