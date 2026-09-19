<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrvx5zbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrvx5zbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:toggle-right" {...props}></Icon>
