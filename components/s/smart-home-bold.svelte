<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjsgpfv6m.css';
import '../../css/g/gb0e29baj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yjsgpfv6m"/><path class="gb0e29baj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smart-home-bold" {...props}></Icon>
