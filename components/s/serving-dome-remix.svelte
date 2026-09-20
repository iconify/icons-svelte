<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mht9c3b7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mht9c3b7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:serving-dome-remix" {...props}></Icon>
