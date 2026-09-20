<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6c_8lp1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6c_8lp1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:servers-solid" {...props}></Icon>
