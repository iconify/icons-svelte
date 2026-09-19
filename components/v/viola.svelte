<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-mm2yblp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a-mm2yblp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:viola" {...props}></Icon>
