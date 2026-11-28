<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu_3zfgud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uu_3zfgud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:salt-shaker" {...props}></Icon>
