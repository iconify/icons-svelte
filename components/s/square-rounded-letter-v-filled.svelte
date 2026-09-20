<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lofyd66wj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lofyd66wj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-letter-v-filled" {...props}></Icon>
