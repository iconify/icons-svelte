<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejvz2abjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ejvz2abjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:waitlist-confirm" {...props}></Icon>
