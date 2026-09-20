<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9tf64bke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="m9tf64bke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:search-circle-solid" {...props}></Icon>
