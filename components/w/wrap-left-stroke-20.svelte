<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lszk02bvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lszk02bvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:wrap-left-stroke-20" {...props}></Icon>
