<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7r9tlz2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k7r9tlz2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-letter-y-filled" {...props}></Icon>
