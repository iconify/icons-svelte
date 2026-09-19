<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gd7thwb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="gd7thwb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:uncharted" {...props}></Icon>
