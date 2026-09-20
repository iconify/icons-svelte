<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewy0tw_xl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewy0tw_xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:x-triangle-solid" {...props}></Icon>
