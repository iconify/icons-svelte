<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6yzs0btw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q6yzs0btw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:santa-hat" {...props}></Icon>
