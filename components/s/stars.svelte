<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1f-ugyov.css';
import '../../css/r/r6-wpcu2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1f-ugyov"/><path class="r6-wpcu2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:stars" {...props}></Icon>
