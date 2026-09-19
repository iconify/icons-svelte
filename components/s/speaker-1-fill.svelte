<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7ksm5bpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="c7ksm5bpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:speaker-1-fill" {...props}></Icon>
