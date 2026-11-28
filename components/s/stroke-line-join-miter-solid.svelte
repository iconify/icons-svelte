<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux7jf8buz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ux7jf8buz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:stroke-line-join-miter-solid" {...props}></Icon>
