<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo_ygpbrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lo_ygpbrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:volume-up-fill" {...props}></Icon>
