<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ueju9xbpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ueju9xbpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:viewfinder" {...props}></Icon>
