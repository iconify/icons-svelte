<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsrjnu5_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zsrjnu5_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:seedling" {...props}></Icon>
