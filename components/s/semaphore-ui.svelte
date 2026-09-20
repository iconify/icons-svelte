<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r057-4e-t.css';
import '../../css/w/we37umbxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="r057-4e-t"/><path class="we37umbxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:semaphore-ui" {...props}></Icon>
