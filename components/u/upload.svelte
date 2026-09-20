<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcmnwab9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="kcmnwab9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:upload" {...props}></Icon>
