<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebqi3hbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebqi3hbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-letter-h" {...props}></Icon>
