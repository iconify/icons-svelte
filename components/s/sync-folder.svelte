<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie56b9byy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ie56b9byy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:sync-folder" {...props}></Icon>
