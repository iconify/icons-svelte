<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aedwb1bzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":35,"height":32};
const content = `<path class="aedwb1bzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:telescope" {...props}></Icon>
