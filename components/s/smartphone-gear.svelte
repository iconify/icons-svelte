<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_f3h57tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_f3h57tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:smartphone-gear" {...props}></Icon>
