<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5o7rqbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v5o7rqbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sayana-press" {...props}></Icon>
