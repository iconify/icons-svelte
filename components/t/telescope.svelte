<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voupb981m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="voupb981m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:telescope" {...props}></Icon>
