<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_cb4lblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":24};
const content = `<path class="k_cb4lblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:vuejs" {...props}></Icon>
