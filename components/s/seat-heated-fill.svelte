<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_x8pkbab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_x8pkbab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:seat-heated-fill" {...props}></Icon>
