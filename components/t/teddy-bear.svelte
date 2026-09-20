<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy7ho_3pd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jy7ho_3pd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:teddy-bear" {...props}></Icon>
