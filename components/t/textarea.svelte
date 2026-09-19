<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q25mes0ml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q25mes0ml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:textarea" {...props}></Icon>
