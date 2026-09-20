<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpbej1ewd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bpbej1ewd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wish-com-light" {...props}></Icon>
