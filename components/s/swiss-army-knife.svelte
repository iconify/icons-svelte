<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ettwtho0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ettwtho0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:swiss-army-knife" {...props}></Icon>
