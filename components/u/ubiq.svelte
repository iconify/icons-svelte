<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca9dfeugk.css';
import '../../css/r/rg1a49h5j.css';
import '../../css/s/scvi-omos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ca9dfeugk"/><path class="rg1a49h5j"/><path class="scvi-omos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ubiq" {...props}></Icon>
