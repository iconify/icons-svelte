<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m78x-1hxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m78x-1hxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:trash" {...props}></Icon>
