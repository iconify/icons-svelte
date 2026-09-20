<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv0d-oj0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hv0d-oj0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:triangle-wave" {...props}></Icon>
