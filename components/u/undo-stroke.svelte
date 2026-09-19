<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asve1nvpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="asve1nvpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:undo-stroke" {...props}></Icon>
