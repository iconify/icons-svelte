<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j48h6jphd.css';
import '../../css/c/ce756l4cb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="j48h6jphd"/><path class="ce756l4cb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:whisparr" {...props}></Icon>
