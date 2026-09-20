<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eac1_7euy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="eac1_7euy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:skull" {...props}></Icon>
