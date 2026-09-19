<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9vs0ebha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o9vs0ebha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:spearfishing" {...props}></Icon>
