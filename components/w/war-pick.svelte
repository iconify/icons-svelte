<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg8pnpb-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tg8pnpb-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:war-pick" {...props}></Icon>
