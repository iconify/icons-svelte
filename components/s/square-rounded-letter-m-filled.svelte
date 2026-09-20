<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlp6wvbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rlp6wvbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-letter-m-filled" {...props}></Icon>
