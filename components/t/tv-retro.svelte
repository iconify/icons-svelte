<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me6dbccby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="me6dbccby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:tv-retro" {...props}></Icon>
