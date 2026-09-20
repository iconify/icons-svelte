<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hg5zuubla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hg5zuubla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:surface-right-filled" {...props}></Icon>
