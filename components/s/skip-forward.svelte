<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpnsiq96y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpnsiq96y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:skip-forward" {...props}></Icon>
