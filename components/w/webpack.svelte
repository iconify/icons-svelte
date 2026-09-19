<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8j3y9bdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":24};
const content = `<path class="w8j3y9bdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:webpack" {...props}></Icon>
