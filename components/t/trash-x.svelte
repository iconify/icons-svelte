<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7jpn2bwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n7jpn2bwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:trash-x" {...props}></Icon>
