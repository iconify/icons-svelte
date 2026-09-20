<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5q-mvb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="x5q-mvb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:sort-alt" {...props}></Icon>
