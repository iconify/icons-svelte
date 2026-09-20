<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj8u2ybur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zj8u2ybur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:volume-minus" {...props}></Icon>
