<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r60j53b-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r60j53b-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:square-dashed-letter-t" {...props}></Icon>
