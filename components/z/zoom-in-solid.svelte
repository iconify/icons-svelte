<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxybgwdbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="oxybgwdbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:zoom-in-solid" {...props}></Icon>
