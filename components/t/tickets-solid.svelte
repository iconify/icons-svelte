<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olej6hbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="olej6hbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:tickets-solid" {...props}></Icon>
