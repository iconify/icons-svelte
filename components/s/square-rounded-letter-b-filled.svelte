<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7xaqs2ci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7xaqs2ci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-letter-b-filled" {...props}></Icon>
