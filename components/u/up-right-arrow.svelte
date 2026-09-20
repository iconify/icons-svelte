<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft_s7-blo.css';
import '../../css/l/l-9yspb3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="ft_s7-blo"/><path class="l-9yspb3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:up-right-arrow" {...props}></Icon>
