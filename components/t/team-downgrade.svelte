<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bce-cpbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bce-cpbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:team-downgrade" {...props}></Icon>
