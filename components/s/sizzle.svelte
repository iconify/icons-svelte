<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/baoz4od4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":896};
const content = `<path class="baoz4od4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:sizzle" {...props}></Icon>
