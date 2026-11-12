<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erzf03bmv.css';
import '../../css/b/br3ht8bop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="erzf03bmv"/><path class="br3ht8bop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:united-airlines" {...props}></Icon>
