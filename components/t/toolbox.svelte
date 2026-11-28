<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er7xp67md.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="er7xp67md"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:toolbox" {...props}></Icon>
