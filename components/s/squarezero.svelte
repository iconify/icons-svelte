<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc5x16b4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="oc5x16b4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:squarezero" {...props}></Icon>
