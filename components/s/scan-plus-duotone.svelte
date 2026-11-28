<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq-k3lbnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary sq-k3lbnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:scan-plus-duotone" {...props}></Icon>
