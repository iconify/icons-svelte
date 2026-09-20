<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1zfn8b1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n1zfn8b1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:waiting-appointments-calendar-solid" {...props}></Icon>
