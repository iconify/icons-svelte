<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xeh2-4bai.css';
import '../../css/s/s8q5ribee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xeh2-4bai"/><path class="s8q5ribee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:stapler-48" {...props}></Icon>
