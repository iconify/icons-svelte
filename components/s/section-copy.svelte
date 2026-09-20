<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf4gkg6yi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uf4gkg6yi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:section-copy" {...props}></Icon>
