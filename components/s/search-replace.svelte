<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oofsbub6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oofsbub6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:search-replace" {...props}></Icon>
