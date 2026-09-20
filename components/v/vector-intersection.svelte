<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnimwlbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnimwlbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vector-intersection" {...props}></Icon>
