<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a11tzybnd.css';
import '../../css/a/ao20o-byk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a11tzybnd"/><path class="ao20o-byk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tianji" {...props}></Icon>
