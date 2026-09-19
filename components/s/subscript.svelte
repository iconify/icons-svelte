<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsg9ixp1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsg9ixp1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:subscript" {...props}></Icon>
