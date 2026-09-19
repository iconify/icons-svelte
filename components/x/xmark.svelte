<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyj9ftbof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="eyj9ftbof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:xmark" {...props}></Icon>
