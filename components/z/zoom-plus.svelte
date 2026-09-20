<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-u6xeb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-u6xeb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:zoom-plus" {...props}></Icon>
