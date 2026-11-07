<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7f9325fo.css';
import '../../css/o/o2n603b_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s7f9325fo"/><path class="o2n603b_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sim-cards-bold-duotone" {...props}></Icon>
