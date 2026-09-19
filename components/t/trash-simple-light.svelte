<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1otcthwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1otcthwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:trash-simple-light" {...props}></Icon>
