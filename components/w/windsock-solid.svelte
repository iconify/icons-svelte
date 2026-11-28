<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a439mjbvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a439mjbvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:windsock-solid" {...props}></Icon>
