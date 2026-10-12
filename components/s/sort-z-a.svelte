<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmnj32bie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmnj32bie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:sort-z-a" {...props}></Icon>
