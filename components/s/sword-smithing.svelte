<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs0f7u05m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qs0f7u05m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sword-smithing" {...props}></Icon>
