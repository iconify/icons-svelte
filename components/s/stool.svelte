<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idh8nnbdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="idh8nnbdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:stool" {...props}></Icon>
