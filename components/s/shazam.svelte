<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/niv8vb25t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="niv8vb25t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:shazam" {...props}></Icon>
