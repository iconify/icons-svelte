<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3awx8gal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u3awx8gal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:visual-inspection" {...props}></Icon>
