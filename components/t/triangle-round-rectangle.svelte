<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1yodib9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w1yodib9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:triangle-round-rectangle" {...props}></Icon>
