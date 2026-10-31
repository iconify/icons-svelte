<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic98o8bay.css';
import '../../css/w/wprsklb5k.css';
import '../../css/o/owe3-0brr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="ic98o8bay"/><path class="wprsklb5k"/><path class="owe3-0brr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:russia" {...props}></Icon>
