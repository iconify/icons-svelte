<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_kog_yln.css';
import '../../css/c/c65-ehvfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s_kog_yln"/><path class="c65-ehvfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tank-farm-48" {...props}></Icon>
