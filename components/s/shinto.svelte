<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkj7i78ez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zkj7i78ez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:shinto" {...props}></Icon>
