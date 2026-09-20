<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq36llb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qq36llb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:tbtc" {...props}></Icon>
