<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo6snj8bg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wo6snj8bg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:slingshot" {...props}></Icon>
