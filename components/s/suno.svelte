<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7ra1sb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":122,"height":122};
const content = `<path clip-rule="evenodd" class="a7ra1sb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:suno" {...props}></Icon>
