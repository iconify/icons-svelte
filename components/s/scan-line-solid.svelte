<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmrq8iauz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmrq8iauz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:scan-line-solid" {...props}></Icon>
