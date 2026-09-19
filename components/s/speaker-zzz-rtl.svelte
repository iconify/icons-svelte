<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1qrn6bqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="l1qrn6bqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:speaker-zzz-rtl" {...props}></Icon>
