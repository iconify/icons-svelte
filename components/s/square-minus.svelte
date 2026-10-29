<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mun6vbc9f.css';
import '../../css/z/z0fhwabjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mun6vbc9f wm-k"/><path class="wm-a z0fhwabjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:square-minus" {...props}></Icon>
