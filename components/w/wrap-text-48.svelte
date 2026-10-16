<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3l5nwb6v.css';
import '../../css/p/pk10can8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b3l5nwb6v"/><path class="pk10can8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wrap-text-48" {...props}></Icon>
