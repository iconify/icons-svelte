<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfza_bc8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kfza_bc8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:smiley-frustrated-16" {...props}></Icon>
