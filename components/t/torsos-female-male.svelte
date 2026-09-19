<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjwhhhtch.css';
import '../../css/j/j4m9ayhmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="xjwhhhtch"/><path class="j4m9ayhmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:torsos-female-male" {...props}></Icon>
