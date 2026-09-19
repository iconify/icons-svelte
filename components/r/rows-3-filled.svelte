<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6pd-lbze.css';
import '../../css/r/rr-fqzblh.css';
import '../../css/u/u4ilukxus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="q6pd-lbze"/><rect class="rr-fqzblh"/><rect class="u4ilukxus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:rows-3-filled" {...props}></Icon>
