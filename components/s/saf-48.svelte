<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edwtppbpi.css';
import '../../css/a/aw5_q9beg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="edwtppbpi"/><path class="aw5_q9beg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:saf-48" {...props}></Icon>
