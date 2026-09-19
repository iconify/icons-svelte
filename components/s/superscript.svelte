<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpfkku9mr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1408};
const content = `<path class="jpfkku9mr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:superscript" {...props}></Icon>
