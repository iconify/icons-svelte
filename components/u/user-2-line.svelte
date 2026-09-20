<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo7oplb2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mo7oplb2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:user-2-line" {...props}></Icon>
