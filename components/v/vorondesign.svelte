<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx_vwr6rk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jx_vwr6rk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:vorondesign" {...props}></Icon>
