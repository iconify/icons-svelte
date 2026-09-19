<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itdv8l7hu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itdv8l7hu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:search-small-plus" {...props}></Icon>
