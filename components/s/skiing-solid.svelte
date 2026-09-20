<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm2nhjbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qm2nhjbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:skiing-solid" {...props}></Icon>
