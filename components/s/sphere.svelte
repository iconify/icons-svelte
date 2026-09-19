<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzzqu0bjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rzzqu0bjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:sphere" {...props}></Icon>
