<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7uf5i4hv.css';
import '../../css/s/sgq0p14ld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f7uf5i4hv"/><circle class="sgq0p14ld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:user-fill" {...props}></Icon>
