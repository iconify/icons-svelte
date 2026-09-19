<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnuza_hyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnuza_hyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:table-columns-merge-filled" {...props}></Icon>
