<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unkg9gb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unkg9gb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:spinner-cog" {...props}></Icon>
