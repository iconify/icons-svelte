<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb_obpjbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zb_obpjbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tube-archivist" {...props}></Icon>
