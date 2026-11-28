<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg6quqbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cg6quqbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-search-solid" {...props}></Icon>
