<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0ze06k3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h0ze06k3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:zoom-in" {...props}></Icon>
