<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia6lvkaoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ia6lvkaoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:status" {...props}></Icon>
