<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmrufobix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="bmrufobix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:serving-dome-hand" {...props}></Icon>
