<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyj7oveoi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hyj7oveoi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shield" {...props}></Icon>
