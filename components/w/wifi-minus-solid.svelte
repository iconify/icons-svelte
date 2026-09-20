<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmbg79_il.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmbg79_il"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:wifi-minus-solid" {...props}></Icon>
