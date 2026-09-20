<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd98yeb8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fd98yeb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:warracker-dark" {...props}></Icon>
