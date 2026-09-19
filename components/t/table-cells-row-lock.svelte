<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xff8fqbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="xff8fqbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:table-cells-row-lock" {...props}></Icon>
