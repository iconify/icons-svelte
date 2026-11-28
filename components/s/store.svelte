<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6e28u54x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6e28u54x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:store" {...props}></Icon>
