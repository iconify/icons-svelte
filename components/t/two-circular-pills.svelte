<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v21e8jbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v21e8jbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:two-circular-pills" {...props}></Icon>
