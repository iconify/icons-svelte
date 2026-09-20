<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u943xibiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u943xibiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:smoke-free-area" {...props}></Icon>
