<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-4gsqb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":24};
const content = `<path class="w-4gsqb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:steam" {...props}></Icon>
