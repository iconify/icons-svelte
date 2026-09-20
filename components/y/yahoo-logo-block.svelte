<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkj5r4bqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pkj5r4bqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:yahoo-logo-block" {...props}></Icon>
