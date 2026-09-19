<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbfnt-e3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vbfnt-e3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:square-plus" {...props}></Icon>
