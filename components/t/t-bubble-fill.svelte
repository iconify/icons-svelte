<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuhbexp4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="nuhbexp4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:t-bubble-fill" {...props}></Icon>
