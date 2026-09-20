<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re_pocbdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="re_pocbdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:synology" {...props}></Icon>
