<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw8fblbvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cw8fblbvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:tshirt-filled" {...props}></Icon>
