<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_3hcou-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_3hcou-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:trash-solid" {...props}></Icon>
