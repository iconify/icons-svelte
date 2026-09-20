<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br4vbfewf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="br4vbfewf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:thermometer-approve" {...props}></Icon>
