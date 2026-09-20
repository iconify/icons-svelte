<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs7gssbtl.css';
import '../../css/s/s1qbw8bvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="hs7gssbtl"/><path class="s1qbw8bvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:search" {...props}></Icon>
