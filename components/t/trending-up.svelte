<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_esy2bes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i_esy2bes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:trending-up" {...props}></Icon>
