<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh9i4cu6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="eh9i4cu6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:volume-level-high-remix" {...props}></Icon>
