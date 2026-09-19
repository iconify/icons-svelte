<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-qlm7bhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c-qlm7bhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:wordpress-alt" {...props}></Icon>
