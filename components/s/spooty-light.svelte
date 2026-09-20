<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyp808bel.css';
import '../../css/g/gq1c8db9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uyp808bel"/><path class="gq1c8db9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:spooty-light" {...props}></Icon>
