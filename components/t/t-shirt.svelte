<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buk6hlfsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="buk6hlfsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:t-shirt" {...props}></Icon>
