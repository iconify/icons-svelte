<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uutp14pfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uutp14pfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:table-remove" {...props}></Icon>
