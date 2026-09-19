<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dldypre7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dldypre7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:shield-check" {...props}></Icon>
