<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk877rgaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nk877rgaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:trophy-outline" {...props}></Icon>
