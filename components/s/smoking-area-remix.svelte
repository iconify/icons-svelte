<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agm10xb6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="agm10xb6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:smoking-area-remix" {...props}></Icon>
