<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz2lpeglw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dz2lpeglw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:share-08" {...props}></Icon>
