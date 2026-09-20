<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6aot1rla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="w6aot1rla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:up-small-solid" {...props}></Icon>
