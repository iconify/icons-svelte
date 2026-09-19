<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea7r9xsmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ea7r9xsmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:screen-dub-o" {...props}></Icon>
