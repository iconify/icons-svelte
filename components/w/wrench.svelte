<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d26mqh20m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d26mqh20m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:wrench" {...props}></Icon>
