<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7v9eabbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7v9eabbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wheat" {...props}></Icon>
