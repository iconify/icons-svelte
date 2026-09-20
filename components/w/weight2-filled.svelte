<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6trnpb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6trnpb7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:weight2-filled" {...props}></Icon>
