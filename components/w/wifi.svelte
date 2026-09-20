<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7a35wbsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k7a35wbsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:wifi" {...props}></Icon>
