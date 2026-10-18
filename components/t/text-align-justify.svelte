<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvt85_2nh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvt85_2nh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:text-align-justify" {...props}></Icon>
