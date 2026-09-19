<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owrpg8bqi.css';
import '../../css/a/ani5aab9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="owrpg8bqi"/><path class="ani5aab9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:tags" {...props}></Icon>
