<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6id_b8os.css';
import '../../css/g/g-29xb7vu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p6id_b8os"/><path class="g-29xb7vu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:voicemail-48" {...props}></Icon>
