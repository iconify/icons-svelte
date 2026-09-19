<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npd735bal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="npd735bal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sling" {...props}></Icon>
