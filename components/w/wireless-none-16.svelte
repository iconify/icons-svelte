<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfqf9xbza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pfqf9xbza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:wireless-none-16" {...props}></Icon>
