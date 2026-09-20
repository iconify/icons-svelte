<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5-6i-bos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5-6i-bos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-letter-p-filled" {...props}></Icon>
