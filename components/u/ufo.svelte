<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6k-cw5wu.css';
import '../../css/e/eppqdoeru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6k-cw5wu"/><path class="eppqdoeru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:ufo" {...props}></Icon>
