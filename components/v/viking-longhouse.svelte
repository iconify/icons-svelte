<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd9adw1-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rd9adw1-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:viking-longhouse" {...props}></Icon>
