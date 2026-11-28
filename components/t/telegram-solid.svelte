<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn8wihhga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sn8wihhga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:telegram-solid" {...props}></Icon>
