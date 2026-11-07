<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/a8neukw-z.css';
import '../../css/o/olic4gb-u.css';
import '../../css/x/x3z2s0btf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="a8neukw-z"/><path class="olic4gb-u"/><path class="x3z2s0btf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-check-broken" {...props}></Icon>
