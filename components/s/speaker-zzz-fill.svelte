<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8lq-06uw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="f8lq-06uw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:speaker-zzz-fill" {...props}></Icon>
