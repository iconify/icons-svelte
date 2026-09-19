<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py9hl5bvu.css';
import '../../css/v/v6af_xb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="py9hl5bvu"/><path class="v6af_xb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:shirt" {...props}></Icon>
