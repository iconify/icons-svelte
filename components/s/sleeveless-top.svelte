<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1en6vb-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r1en6vb-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sleeveless-top" {...props}></Icon>
