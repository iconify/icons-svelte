<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz8pd-b6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bz8pd-b6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:sippy-cup" {...props}></Icon>
