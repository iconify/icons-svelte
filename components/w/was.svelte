<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp2sc6bbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cp2sc6bbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:was" {...props}></Icon>
