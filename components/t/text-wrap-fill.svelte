<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otd380onp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="otd380onp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:text-wrap-fill" {...props}></Icon>
