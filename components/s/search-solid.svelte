<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3ar17e1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3ar17e1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:search-solid" {...props}></Icon>
