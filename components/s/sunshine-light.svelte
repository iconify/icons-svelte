<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igxg7ab5n.css';
import '../../css/a/aw61reb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="igxg7ab5n"/><path class="aw61reb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sunshine-light" {...props}></Icon>
