<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mycu2ya9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mycu2ya9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:tag-x" {...props}></Icon>
