<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcs_icv0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lcs_icv0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:solus" {...props}></Icon>
