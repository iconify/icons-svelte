<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqa1w4vfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iqa1w4vfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:spotting-scope" {...props}></Icon>
