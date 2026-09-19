<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/leuvwevba.css';
import '../../css/i/i6mj3y4rj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="leuvwevba"/><path class="i6mj3y4rj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:tropical-storm-tracks" {...props}></Icon>
