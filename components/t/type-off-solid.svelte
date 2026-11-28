<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6ul5xvrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6ul5xvrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:type-off-solid" {...props}></Icon>
