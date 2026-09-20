<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3xa-ib0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u3xa-ib0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:steelseries" {...props}></Icon>
