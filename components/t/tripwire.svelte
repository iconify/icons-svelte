<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oq__px-mj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oq__px-mj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tripwire" {...props}></Icon>
