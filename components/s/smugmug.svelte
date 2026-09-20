<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-vjr-y9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-vjr-y9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:smugmug" {...props}></Icon>
