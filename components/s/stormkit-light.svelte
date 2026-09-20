<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnqu6b8yq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dnqu6b8yq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:stormkit-light" {...props}></Icon>
