<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf39gg-ix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nf39gg-ix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:vertical-distribution-top" {...props}></Icon>
