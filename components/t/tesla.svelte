<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k47x0ekmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k47x0ekmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:tesla" {...props}></Icon>
