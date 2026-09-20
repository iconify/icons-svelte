<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py9te0bmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="py9te0bmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:shape-triangle" {...props}></Icon>
