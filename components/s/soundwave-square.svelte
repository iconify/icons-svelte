<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/is8se_vww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="is8se_vww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:soundwave-square" {...props}></Icon>
