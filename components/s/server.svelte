<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzcj2mb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bzcj2mb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:server" {...props}></Icon>
