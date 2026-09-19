<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bg_orq4_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bg_orq4_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:stahlhelm" {...props}></Icon>
