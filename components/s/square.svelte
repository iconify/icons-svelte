<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aockpub2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aockpub2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:square" {...props}></Icon>
