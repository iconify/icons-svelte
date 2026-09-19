<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3-by5b3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a3-by5b3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:square-line-vertical" {...props}></Icon>
