<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us55wqbte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="us55wqbte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:scooter-outline" {...props}></Icon>
