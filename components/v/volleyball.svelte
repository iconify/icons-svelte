<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvl60l-3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gvl60l-3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:volleyball" {...props}></Icon>
