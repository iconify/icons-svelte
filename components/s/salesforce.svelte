<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpga_ecty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hpga_ecty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:salesforce" {...props}></Icon>
