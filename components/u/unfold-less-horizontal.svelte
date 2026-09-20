<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s73-gj2tt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s73-gj2tt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:unfold-less-horizontal" {...props}></Icon>
