<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkgk_7lou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkgk_7lou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:story-post" {...props}></Icon>
