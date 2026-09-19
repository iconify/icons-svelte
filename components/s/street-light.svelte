<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1__e5bal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b1__e5bal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:street-light" {...props}></Icon>
