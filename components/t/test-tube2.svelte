<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1-_wk_vx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i1-_wk_vx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:test-tube2" {...props}></Icon>
