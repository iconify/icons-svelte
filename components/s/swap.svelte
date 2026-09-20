<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myetzitsr.css';
import '../../css/f/f46ywubav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="myetzitsr"/><path class="f46ywubav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:swap" {...props}></Icon>
