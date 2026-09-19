<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqf-fkblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gqf-fkblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:wolf-howl" {...props}></Icon>
