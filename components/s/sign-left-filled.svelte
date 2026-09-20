<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlrq40rat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xlrq40rat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sign-left-filled" {...props}></Icon>
