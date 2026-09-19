<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spdsblbne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="spdsblbne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:ui-radios-grid" {...props}></Icon>
