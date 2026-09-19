<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqr9zzbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hqr9zzbjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:table-row-before" {...props}></Icon>
