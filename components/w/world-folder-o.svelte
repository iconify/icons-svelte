<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amb6xmb9p.css';
import '../../css/b/bt5hmxdsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="amb6xmb9p"/><path class="bt5hmxdsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:world-folder-o" {...props}></Icon>
