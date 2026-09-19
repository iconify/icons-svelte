<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfldv9gmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qfldv9gmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:summits" {...props}></Icon>
