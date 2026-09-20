<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g67ggebyw.css';
import '../../css/g/geuo8cbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="g67ggebyw"/><path class="geuo8cbkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:shoe-11" {...props}></Icon>
