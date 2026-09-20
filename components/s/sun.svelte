<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmawd3fxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rmawd3fxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sun" {...props}></Icon>
