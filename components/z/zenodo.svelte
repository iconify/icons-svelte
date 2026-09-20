<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt3ev1jtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rt3ev1jtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:zenodo" {...props}></Icon>
