<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4pmglbhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="v4pmglbhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:wall-fill" {...props}></Icon>
