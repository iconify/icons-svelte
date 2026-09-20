<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7y0q8bps.css';
import '../../css/d/d25y6j89z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7y0q8bps"/><path class="d25y6j89z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:shield-24" {...props}></Icon>
