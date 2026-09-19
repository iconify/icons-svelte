<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7qk6dbfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":1024};
const content = `<path class="d7qk6dbfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:selectionsymbol" {...props}></Icon>
