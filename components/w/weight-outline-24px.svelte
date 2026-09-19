<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhiy8ctqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hhiy8ctqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:weight-outline-24px" {...props}></Icon>
