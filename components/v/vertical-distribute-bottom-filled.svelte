<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q33hpgb-j.css';
import '../../css/i/i5r4e0b0g.css';
import '../../css/s/s6a_vl58s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q33hpgb-j"/><rect class="i5r4e0b0g"/><rect class="s6a_vl58s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:vertical-distribute-bottom-filled" {...props}></Icon>
