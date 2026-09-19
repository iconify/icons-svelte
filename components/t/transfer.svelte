<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxqbi4buz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxqbi4buz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:transfer" {...props}></Icon>
