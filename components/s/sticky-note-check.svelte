<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsmtwzb_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gsmtwzb_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:sticky-note-check" {...props}></Icon>
