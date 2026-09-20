<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edssndbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="edssndbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:settings" {...props}></Icon>
