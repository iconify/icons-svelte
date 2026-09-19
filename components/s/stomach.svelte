<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r80dywhha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r80dywhha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:stomach" {...props}></Icon>
