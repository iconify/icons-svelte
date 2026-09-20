<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sugnyfphq.css';
import '../../css/i/i9bnjpm9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sugnyfphq"/><path class="i9bnjpm9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:xcm" {...props}></Icon>
