<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifdnxp4wp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ifdnxp4wp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:wand" {...props}></Icon>
