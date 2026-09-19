<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud72a57ps.css';
import '../../css/b/byocr9c0k.css';
import '../../css/v/vj8lj592n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ud72a57ps"/><path class="byocr9c0k"/><path class="vj8lj592n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-buffer-outline" {...props}></Icon>
