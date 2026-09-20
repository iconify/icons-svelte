<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh582hbel.css';
import '../../css/e/e6zc0ccud.css';
import '../../css/b/bvqr90b7l.css';
import '../../css/f/fsaxo7b-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eh582hbel"/><path class="e6zc0ccud"/><path class="bvqr90b7l"/><path class="fsaxo7b-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:streamlink" {...props}></Icon>
