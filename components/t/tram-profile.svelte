<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo0bw59ba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wo0bw59ba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tram-profile" {...props}></Icon>
