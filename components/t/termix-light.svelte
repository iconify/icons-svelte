<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b45l35wcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b45l35wcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:termix-light" {...props}></Icon>
