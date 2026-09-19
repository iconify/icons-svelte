<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvejaebos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvejaebos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-plus-square-light" {...props}></Icon>
