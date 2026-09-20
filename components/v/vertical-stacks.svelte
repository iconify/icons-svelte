<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg1xs5bde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jg1xs5bde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:vertical-stacks" {...props}></Icon>
