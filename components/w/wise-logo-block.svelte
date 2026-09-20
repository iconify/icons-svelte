<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl1__ds7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rl1__ds7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:wise-logo-block" {...props}></Icon>
