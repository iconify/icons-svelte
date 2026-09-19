<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lebys2svk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lebys2svk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:small-long-right" {...props}></Icon>
