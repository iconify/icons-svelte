<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzv-z1sfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vzv-z1sfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:scopus" {...props}></Icon>
