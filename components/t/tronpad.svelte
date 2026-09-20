<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cos6pzg3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cos6pzg3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:tronpad" {...props}></Icon>
