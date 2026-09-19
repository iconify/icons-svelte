<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezeu5xbia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ezeu5xbia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:visual-studio" {...props}></Icon>
