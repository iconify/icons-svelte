<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlggubcpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlggubcpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:stretch-vertical" {...props}></Icon>
