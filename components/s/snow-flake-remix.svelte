<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwj-bqk-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vwj-bqk-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:snow-flake-remix" {...props}></Icon>
