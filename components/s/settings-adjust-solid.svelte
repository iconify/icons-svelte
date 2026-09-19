<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxze5ab0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxze5ab0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:settings-adjust-solid" {...props}></Icon>
