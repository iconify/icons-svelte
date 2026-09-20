<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnxp0mg7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mnxp0mg7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:x-diamond-solid" {...props}></Icon>
