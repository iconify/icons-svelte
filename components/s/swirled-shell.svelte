<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjh4zn-ur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xjh4zn-ur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:swirled-shell" {...props}></Icon>
