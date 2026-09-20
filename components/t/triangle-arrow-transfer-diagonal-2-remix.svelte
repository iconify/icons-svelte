<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia5zytlyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ia5zytlyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:triangle-arrow-transfer-diagonal-2-remix" {...props}></Icon>
