<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7b-_ybbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d7b-_ybbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:volume-2-outline" {...props}></Icon>
