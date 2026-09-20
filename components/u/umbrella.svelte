<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia_j65b2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ia_j65b2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:umbrella" {...props}></Icon>
