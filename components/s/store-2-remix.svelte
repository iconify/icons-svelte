<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg-68ml4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gg-68ml4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:store-2-remix" {...props}></Icon>
