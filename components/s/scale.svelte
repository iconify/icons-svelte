<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc6yksbcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="uc6yksbcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:scale" {...props}></Icon>
