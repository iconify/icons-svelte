<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nml4dbbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nml4dbbpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:thumb-down-outline" {...props}></Icon>
