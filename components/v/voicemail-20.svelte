<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq7odubmz.css';
import '../../css/o/ot9dk8dyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="eq7odubmz"/><path class="ot9dk8dyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:voicemail-20" {...props}></Icon>
