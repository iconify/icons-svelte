<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab48hf36a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ab48hf36a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tarot-21-the-world" {...props}></Icon>
