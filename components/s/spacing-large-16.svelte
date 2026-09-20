<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2el319gf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v2el319gf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:spacing-large-16" {...props}></Icon>
