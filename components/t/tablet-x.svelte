<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrhv1bcks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrhv1bcks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:tablet-x" {...props}></Icon>
