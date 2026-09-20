<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enyhqqbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="enyhqqbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:search1api" {...props}></Icon>
