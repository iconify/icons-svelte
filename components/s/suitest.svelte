<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj9kqqb1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nj9kqqb1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:suitest" {...props}></Icon>
