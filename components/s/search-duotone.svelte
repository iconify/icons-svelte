<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw0v5yb-n.css';
import '../../css/f/f9b-7_qnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gw0v5yb-n"/><path class="f9b-7_qnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:search-duotone" {...props}></Icon>
