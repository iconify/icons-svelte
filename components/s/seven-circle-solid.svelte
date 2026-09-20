<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucj6lf7oo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ucj6lf7oo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:seven-circle-solid" {...props}></Icon>
