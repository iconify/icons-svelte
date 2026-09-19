<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3ok68b9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x3ok68b9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:sorcerer-hat" {...props}></Icon>
