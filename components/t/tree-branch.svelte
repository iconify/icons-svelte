<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv7xipbea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bv7xipbea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tree-branch" {...props}></Icon>
