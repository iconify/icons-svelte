<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzh6aom-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="rzh6aom-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:telescope" {...props}></Icon>
