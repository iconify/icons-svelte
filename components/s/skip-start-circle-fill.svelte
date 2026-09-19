<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nml_d7_9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nml_d7_9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:skip-start-circle-fill" {...props}></Icon>
