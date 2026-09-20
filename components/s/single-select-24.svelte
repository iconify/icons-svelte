<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jydc_mb-y.css';
import '../../css/t/tbcp7-bab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jydc_mb-y"/><path class="tbcp7-bab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:single-select-24" {...props}></Icon>
