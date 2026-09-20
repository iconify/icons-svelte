<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqecm5lrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gqecm5lrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:watch-outline" {...props}></Icon>
