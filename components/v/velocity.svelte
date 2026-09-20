<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exaqg9f9e.css';
import '../../css/j/joioafbdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":300};
const content = `<path paint-order="fill markers stroke" class="exaqg9f9e"/><path class="joioafbdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:velocity" {...props}></Icon>
