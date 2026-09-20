<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kht5u-kyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kht5u-kyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-question-line" {...props}></Icon>
