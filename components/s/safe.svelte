<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5mt7nr3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g5mt7nr3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:safe" {...props}></Icon>
