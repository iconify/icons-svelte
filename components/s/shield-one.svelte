<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xohs8_ozi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xohs8_ozi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:shield-one" {...props}></Icon>
