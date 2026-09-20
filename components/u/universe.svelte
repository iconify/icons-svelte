<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itjmgykbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-3,"top":-3};
const content = `<path class="itjmgykbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:universe" {...props}></Icon>
