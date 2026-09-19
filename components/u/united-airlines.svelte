<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hltws9d4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hltws9d4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:united-airlines" {...props}></Icon>
