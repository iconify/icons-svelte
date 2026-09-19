<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofjs243ce.css';
import '../../css/h/ho71zpbvj.css';
import '../../css/i/idfn3mciq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ofjs243ce"/><path class="ho71zpbvj"/><path class="idfn3mciq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:wine-outline" {...props}></Icon>
