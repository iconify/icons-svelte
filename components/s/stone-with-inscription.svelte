<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/miqz-ooth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="miqz-ooth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:stone-with-inscription" {...props}></Icon>
