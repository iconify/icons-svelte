<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxz2cui4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oxz2cui4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:starknet" {...props}></Icon>
