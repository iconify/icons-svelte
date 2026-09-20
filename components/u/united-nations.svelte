<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-k22fbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-k22fbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:united-nations" {...props}></Icon>
