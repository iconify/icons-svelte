<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8r359d7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8r359d7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:unfold-less" {...props}></Icon>
