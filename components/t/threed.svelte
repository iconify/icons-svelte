<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfgx_pj9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":1024};
const content = `<path class="hfgx_pj9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:threed" {...props}></Icon>
