<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv1c6chiz.css';
import '../../css/y/y471xbw7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kv1c6chiz"/><path clip-rule="evenodd" class="y471xbw7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:stereo-left-16" {...props}></Icon>
