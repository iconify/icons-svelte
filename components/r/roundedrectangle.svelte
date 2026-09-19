<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v21nj7bdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="v21nj7bdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:roundedrectangle" {...props}></Icon>
