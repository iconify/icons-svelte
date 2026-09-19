<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty4atgz1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ty4atgz1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:shield" {...props}></Icon>
