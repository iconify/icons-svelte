<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/gh-4n77zw.css';
import '../../css/q/q216lkbrx.css';
import '../../css/e/efkc1gbdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gh-4n77zw"/><path class="q216lkbrx"/><path class="efkc1gbdu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:view-off-slash" {...props}></Icon>
