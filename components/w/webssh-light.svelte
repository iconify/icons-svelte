<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hod_yhbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hod_yhbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:webssh-light" {...props}></Icon>
