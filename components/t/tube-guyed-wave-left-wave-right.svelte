<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5d2v1bhr.css';
import '../../css/y/y59k77qlt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v5d2v1bhr"/><path class="y59k77qlt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:tube-guyed-wave-left-wave-right" {...props}></Icon>
