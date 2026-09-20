<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qho7iu1hx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qho7iu1hx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:witch" {...props}></Icon>
