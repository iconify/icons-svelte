<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q656w8_df.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q656w8_df"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:water-bottle" {...props}></Icon>
