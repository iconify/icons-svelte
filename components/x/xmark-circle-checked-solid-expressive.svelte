<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg3wixb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dg3wixb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:xmark-circle-checked-solid-expressive" {...props}></Icon>
