<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt-t8abnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pt-t8abnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:transit-vehicle-with-destination-display-on-railway-track" {...props}></Icon>
