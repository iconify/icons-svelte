<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh3w2t_7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bh3w2t_7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tree-growth" {...props}></Icon>
