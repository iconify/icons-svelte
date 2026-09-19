<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6aeqburm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v6aeqburm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:wolf-head" {...props}></Icon>
