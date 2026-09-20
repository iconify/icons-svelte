<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sld39kbbp.css';
import '../../css/o/o4c4j_blr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sld39kbbp"/><path class="o4c4j_blr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:sidebar-expand-16" {...props}></Icon>
