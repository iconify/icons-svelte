<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtjdixb9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dtjdixb9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tower-fall" {...props}></Icon>
