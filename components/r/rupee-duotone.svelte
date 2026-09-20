<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buan6_edz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="buan6_edz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:rupee-duotone" {...props}></Icon>
