<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spd40nbft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="spd40nbft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:shield-fill-20" {...props}></Icon>
