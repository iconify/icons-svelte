<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbbc3kb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbbc3kb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:visual-studio" {...props}></Icon>
