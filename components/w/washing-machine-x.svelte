<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3um52bcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3um52bcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:washing-machine-x" {...props}></Icon>
