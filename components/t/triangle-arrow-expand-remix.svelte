<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mihpvbc6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mihpvbc6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:triangle-arrow-expand-remix" {...props}></Icon>
