<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn5osginn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sn5osginn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:standard-notes-dark" {...props}></Icon>
