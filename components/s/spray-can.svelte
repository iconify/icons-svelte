<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ica58birs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ica58birs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:spray-can" {...props}></Icon>
