<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq1hqm0hv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zq1hqm0hv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:trophy-fill" {...props}></Icon>
