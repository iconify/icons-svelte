<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhua0w9kb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lhua0w9kb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wire" {...props}></Icon>
