<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss29dgbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ss29dgbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:rupee-circle-solid" {...props}></Icon>
