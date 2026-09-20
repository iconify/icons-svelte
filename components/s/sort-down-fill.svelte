<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od0ifz31h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="od0ifz31h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:sort-down-fill" {...props}></Icon>
