<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-vd53b8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="c-vd53b8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:teamviewer" {...props}></Icon>
