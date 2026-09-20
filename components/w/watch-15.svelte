<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvqgryrqk.css';
import '../../css/t/taxqw2bmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kvqgryrqk"/><path class="taxqw2bmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:watch-15" {...props}></Icon>
