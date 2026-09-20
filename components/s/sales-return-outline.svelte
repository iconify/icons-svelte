<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkdf4u1mn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jkdf4u1mn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:sales-return-outline" {...props}></Icon>
