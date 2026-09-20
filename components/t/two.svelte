<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb_0tkhsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nb_0tkhsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:two" {...props}></Icon>
