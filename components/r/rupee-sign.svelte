<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz1m2xbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="dz1m2xbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:rupee-sign" {...props}></Icon>
