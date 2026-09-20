<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um0u04m2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="um0u04m2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:venn-diagram-solid" {...props}></Icon>
