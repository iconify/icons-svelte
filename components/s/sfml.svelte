<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x982fhkgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x982fhkgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sfml" {...props}></Icon>
