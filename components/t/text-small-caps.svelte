<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acb0atomk.css';
import '../../css/g/gb7o9bbig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="acb0atomk"/><path class="gb7o9bbig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-small-caps" {...props}></Icon>
