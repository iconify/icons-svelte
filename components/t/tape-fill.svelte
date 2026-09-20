<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2mycwnne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2mycwnne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:tape-fill" {...props}></Icon>
