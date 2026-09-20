<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0o91oa8d.css';
import '../../css/n/nzums1brs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0o91oa8d"/><path class="nzums1brs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:train-4-line" {...props}></Icon>
