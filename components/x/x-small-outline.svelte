<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kks44q3cb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kks44q3cb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:x-small-outline" {...props}></Icon>
