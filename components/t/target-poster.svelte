<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/befr52blg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="befr52blg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:target-poster" {...props}></Icon>
