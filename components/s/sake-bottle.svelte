<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz5vqb9ya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uz5vqb9ya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sake-bottle" {...props}></Icon>
