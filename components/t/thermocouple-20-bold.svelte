<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc82xxbku.css';
import '../../css/i/im-vrsb-c.css';
import '../../css/a/apexb8rod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rc82xxbku"/><path class="im-vrsb-c"/><path class="apexb8rod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermocouple-20-bold" {...props}></Icon>
