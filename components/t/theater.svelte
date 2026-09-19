<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l431ykn9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l431ykn9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:theater" {...props}></Icon>
