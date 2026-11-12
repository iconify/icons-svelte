<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0xlexmxx.css';
import '../../css/u/u3k9wcbgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u0xlexmxx"/><path class="u3k9wcbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:toodoom-dark" {...props}></Icon>
