<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gc0qugbit.css';
import '../../css/n/nvekhcocz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gc0qugbit"/><path class="nvekhcocz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:sort-amount-desc" {...props}></Icon>
