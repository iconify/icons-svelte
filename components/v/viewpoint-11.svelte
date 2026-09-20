<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drvx3jbdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="drvx3jbdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:viewpoint-11" {...props}></Icon>
