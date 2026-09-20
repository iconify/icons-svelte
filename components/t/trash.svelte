<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpv0g5b1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bpv0g5b1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:trash" {...props}></Icon>
