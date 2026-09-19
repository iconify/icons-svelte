<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b44mov6pv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b44mov6pv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:theater-curtains" {...props}></Icon>
