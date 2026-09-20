<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv30cvl2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bv30cvl2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-x" {...props}></Icon>
