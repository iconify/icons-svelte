<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsir6wkji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qsir6wkji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:truck" {...props}></Icon>
