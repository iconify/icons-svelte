<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mms9xzmvs.css';
import '../../css/a/a2h-5ubrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mms9xzmvs"/><path clip-rule="evenodd" class="a2h-5ubrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sticker-smile-circle-2-bold" {...props}></Icon>
