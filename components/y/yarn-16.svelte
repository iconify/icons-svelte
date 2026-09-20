<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/josx51y5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="josx51y5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:yarn-16" {...props}></Icon>
