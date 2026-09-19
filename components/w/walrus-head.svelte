<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6z0351mq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l6z0351mq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:walrus-head" {...props}></Icon>
