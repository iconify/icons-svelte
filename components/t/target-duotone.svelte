<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9m23kb1m.css';
import '../../css/s/sz3jedbeq.css';
import '../../css/x/x_4guwbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l9m23kb1m"/><path class="sz3jedbeq"/><path class="x_4guwbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:target-duotone" {...props}></Icon>
