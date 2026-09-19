<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9unun_6a.css';
import '../../css/q/q5don451u.css';
import '../../css/u/uaycyrbmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="x9unun_6a"/><path class="q5don451u"/><path class="uaycyrbmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:tape-drive-solid-alerted" {...props}></Icon>
