<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpl0je8ew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hpl0je8ew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:wifi-alert-attention-bold" {...props}></Icon>
