<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab_bnglml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="ab_bnglml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:wizard" {...props}></Icon>
