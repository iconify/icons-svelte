<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6df3db1i.css';
import '../../css/b/bw7r1grov.css';
import '../../css/e/emsprcb7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="s6df3db1i"/><path class="bw7r1grov"/><path class="emsprcb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tautulli" {...props}></Icon>
