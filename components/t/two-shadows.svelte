<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymfss1b1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ymfss1b1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:two-shadows" {...props}></Icon>
