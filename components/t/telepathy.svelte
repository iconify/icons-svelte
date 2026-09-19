<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozd69z-yo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ozd69z-yo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:telepathy" {...props}></Icon>
