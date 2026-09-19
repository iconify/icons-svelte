<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa6-ti_2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aa6-ti_2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:save-as" {...props}></Icon>
