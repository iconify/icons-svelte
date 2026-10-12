<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u96b__bac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u96b__bac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:subset-proper-of" {...props}></Icon>
