<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hz606i7re.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hz606i7re"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:stone-axe" {...props}></Icon>
