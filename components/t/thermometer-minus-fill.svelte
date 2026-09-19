<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqy0_y_xf.css';
import '../../css/w/w4-6i1bne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="qqy0_y_xf"/><path class="w4-6i1bne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:thermometer-minus-fill" {...props}></Icon>
