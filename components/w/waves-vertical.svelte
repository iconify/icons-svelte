<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slu3g-y_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slu3g-y_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:waves-vertical" {...props}></Icon>
