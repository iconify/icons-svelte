<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usnj5m19l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="usnj5m19l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:wand-check" {...props}></Icon>
