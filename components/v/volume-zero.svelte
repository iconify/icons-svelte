<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a21tmvbyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a21tmvbyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:volume-zero" {...props}></Icon>
