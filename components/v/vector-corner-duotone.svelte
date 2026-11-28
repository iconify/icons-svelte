<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8qpqobef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p8qpqobef primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:vector-corner-duotone" {...props}></Icon>
