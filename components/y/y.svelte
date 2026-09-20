<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obdes7tlt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="obdes7tlt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:y" {...props}></Icon>
