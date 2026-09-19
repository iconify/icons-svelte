<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6t53cwua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k6t53cwua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tinker" {...props}></Icon>
