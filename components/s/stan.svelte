<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugvei2bjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugvei2bjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:stan" {...props}></Icon>
