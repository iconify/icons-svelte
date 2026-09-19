<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak5czckoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ak5czckoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sword-spin" {...props}></Icon>
